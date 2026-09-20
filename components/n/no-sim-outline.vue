<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu-uiyk7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-sim-outline" /></template>
<style>
.bu-uiyk7b {
  fill: currentColor;
  d: path("m19 16.425l-1-1V4.615q0-.23-.192-.423T17.384 4H10.85L8.696 6.154l-.719-.708L10.423 3h6.962q.69 0 1.153.463T19 4.615zm1.423 5.683L6.577 8.262L6 8.839v10.546q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.423v-1.121l1 1v.12q0 .691-.462 1.154T17.384 21H6.616q-.691 0-1.153-.462T5 19.385V8.423l.87-.87l-3.824-3.822l.714-.708l18.37 18.371zm-8.138-8.171");
}

</style>
