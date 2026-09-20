<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3fq8e7_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g3fq8e7_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-abnormal-outline" /></template>
