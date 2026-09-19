<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7mdj_t3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":581,"height":512};
const content = `<path class="l7mdj_t3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:r-project" /></template>
