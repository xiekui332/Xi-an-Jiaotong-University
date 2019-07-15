<template>
    <div id="manage">
        <div class="ma-header">
            <div class="pub-css ma-logo">

            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    },

    methods: {

    },

    mounted() {

    }
}
</script>

<style lang="less" scoped>
#manage{
    .pub-css{
        background: url('../../assets/img/css_sprites.png');
        background-size:440px 391px; 
    }
    min-height: 100%;
    .ma-header{
        height: 64px;
        background: #004E97;
        display: flex;
        .ma-logo{
            width: 40px;
            height: 40px;
            align-items: center;
            background-position: -316px -10px;
        }
    }
}
</style>


