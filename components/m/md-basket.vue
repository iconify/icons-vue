<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgq1ff3gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hgq1ff3gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-basket" /></template>
