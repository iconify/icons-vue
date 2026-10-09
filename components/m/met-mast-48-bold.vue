<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnyb1hbmp.css';
import '../../css/y/yh_jzue5r.css';
import '../../css/a/afh_lob9l.css';
import '../../css/y/yd64m07av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnyb1hbmp"/><path class="yh_jzue5r"/><path class="afh_lob9l"/><path class="yd64m07av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:met-mast-48-bold" /></template>
