<template>
    <div class="v-carousel-item">
        <img :src="require('../assets/images' + item_data.image + '.jpg') :alt='item_data.alt'>
    </div>
</template>


<script>
export default {
    name: 'v-carousel-item',
    props: {
        item_data: {
            type: Object,
            default: () => {}
        }
    },
    data() {
        return {}
    },
    computed: {}
}
</script>

<style scoped>

</style>