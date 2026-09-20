<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ihzybso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:store-outline-rounded" /></template>
<style>
.v8ihzybso {
  fill: currentColor;
  d: path("M4.923 4.5h14.154q.212 0 .356.144t.144.357t-.144.356t-.356.143H4.923q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143m.385 15q-.343 0-.576-.232t-.232-.576V13.5h-.444q-.379 0-.631-.305t-.152-.684l1-4.384q.062-.274.288-.45q.226-.177.514-.177h13.85q.288 0 .514.176q.226.177.288.451l1 4.384q.1.38-.152.684t-.63.305H19.5V19q0 .213-.144.356t-.357.144t-.356-.144T18.5 19v-5.5h-5v5.192q0 .344-.232.576t-.576.232zm.192-1h7v-5h-7zm-1.22-6h15.44zm0 0h15.44l-.928-4H5.208z");
}

</style>
