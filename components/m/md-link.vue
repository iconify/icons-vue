<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yujzi7b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yujzi7b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-link" /></template>
