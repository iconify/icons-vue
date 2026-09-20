<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hct2ytnjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trolley-cable-car" /></template>
<style>
.hct2ytnjp {
  fill: currentColor;
  d: path("M7.25 20v-.308L8.942 18H4v-1h1V6H4V5h3.75V3.77h8.5V5H20v1h-1v11h1v1h-4.962l1.693 1.692V20h-1.039l-2-2H10.29l-2 2zm5.25-9.461H18v-3.77h-5.5zm-6.5 0h5.5v-3.77H6zm6.004 4.75q.41 0 .683-.274t.274-.685t-.274-.697t-.684-.287t-.697.287t-.287.697t.287.684t.697.275");
}

</style>
