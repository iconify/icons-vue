<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3dtwx_cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x3dtwx_cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:whistling" /></template>
