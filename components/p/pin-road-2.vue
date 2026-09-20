<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3stxb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-road-2" /></template>
<style>
.fh3stxb-q {
  fill: currentColor;
  d: path("M14.135 20v-2.866h1V20zm0-6.558v-2.865h1v2.865zm0-6.558V4h1v2.885zM20.019 20L17.673 4h1L21 20zm-13.61-.064q-.113-.064-.175-.192l-.083-.193q-.455-1.026-1.336-1.747q-.88-.722-1.496-1.642q-.342-.495-.513-1.076q-.171-.58-.171-1.191q0-1.664 1.154-2.844t2.807-1.18q1.675 0 2.879 1.109t1.204 2.756q0 .633-.152 1.262t-.52 1.164q-.615.925-1.486 1.651t-1.36 1.736l-.084.19q-.064.13-.181.196Q6.779 20 6.65 20t-.241-.064m1.435-4.88q.501-.5.501-1.19q0-.691-.5-1.192t-1.192-.501t-1.192.501t-.5 1.192t.5 1.19t1.192.502t1.191-.501m3.016-6.051q-.207-.194-.417-.346t-.46-.312L10.617 4h.98z");
}

</style>
