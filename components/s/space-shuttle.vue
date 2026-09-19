<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_-p3bvlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2176,"height":1408};
const content = `<path class="j_-p3bvlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:space-shuttle" /></template>
