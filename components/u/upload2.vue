<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqyxfs48f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hqyxfs48f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:upload2" /></template>
