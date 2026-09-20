<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/z/zmslvebwb.css';
import '../../css/u/uc7v4v_cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 4)" class="jtowsomii"><path class="zmslvebwb"/><circle class="uc7v4v_cp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:wifi-error" /></template>
