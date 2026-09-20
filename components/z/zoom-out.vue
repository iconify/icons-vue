<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mr99q4ujx.css';
import '../../css/q/qdk7iu9kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 3)" class="jtowsomii"><circle class="mr99q4ujx"/><path class="qdk7iu9kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:zoom-out" /></template>
