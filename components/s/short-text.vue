<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ux_fb-o.css';
import '../../css/y/y766n9b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ux_fb-o"/><path class="y766n9b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:short-text" /></template>
