<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy_v_8_dd.css';
import '../../css/a/a38e_428a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wy_v_8_dd"/><path class="a38e_428a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:zig" /></template>
