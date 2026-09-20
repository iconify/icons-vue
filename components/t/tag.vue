<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thfp2fdkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="thfp2fdkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tag" /></template>
