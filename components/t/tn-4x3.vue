<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-p6sxs_x.css';
import '../../css/i/ibd8u0c8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="m-p6sxs_x"/><path class="ibd8u0c8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:tn-4x3" /></template>
