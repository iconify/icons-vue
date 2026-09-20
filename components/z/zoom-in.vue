<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mr99q4ujx.css';
import '../../css/o/ok2yorv_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 3)" class="jtowsomii"><circle class="mr99q4ujx"/><path class="ok2yorv_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:zoom-in" /></template>
