<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc2_ucbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vc2_ucbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:volume-off-ltr" /></template>
