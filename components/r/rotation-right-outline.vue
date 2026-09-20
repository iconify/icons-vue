<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owy-2xwyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="owy-2xwyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rotation-right-outline" /></template>
