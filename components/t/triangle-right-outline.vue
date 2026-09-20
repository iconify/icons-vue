<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlbuiq_zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xlbuiq_zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-right-outline" /></template>
