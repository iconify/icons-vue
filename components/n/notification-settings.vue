<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrhc-ac1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-settings" /></template>
<style>
.hrhc-ac1a {
  fill: currentColor;
  d: path("M12 21.385q-.671 0-1.143-.472t-.472-1.144h3.23q0 .672-.472 1.144T12 21.385m-7-2.616v-1h1.616V9.846q0-1.83 1.089-3.263q1.09-1.433 2.826-1.927q-.198.535-.3 1.096t-.102 1.133q0 1.47.592 2.699t1.602 2.1q1.01.874 2.313 1.279t2.749.199v4.607H19v1zm10.923-8l-.107-.885q-.474-.105-.89-.32q-.416-.214-.749-.587l-.835.334l-.538-.815l.688-.577q-.165-.517-.165-1.035t.165-1.034l-.688-.577l.538-.815l.835.334q.314-.373.74-.587q.425-.215.899-.32L15.923 3h1l.108.884q.473.106.899.32t.74.588l.834-.334l.538.815l-.688.577q.165.517.165 1.035t-.165 1.034l.688.577l-.538.815l-.835-.334q-.332.373-.749.588q-.416.214-.89.32l-.107.884zm2.028-2.357q.626-.626.626-1.528q0-.901-.626-1.527t-1.528-.626t-1.528.626t-.626 1.527t.626 1.528t1.528.626t1.528-.626");
}

</style>
