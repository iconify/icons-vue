<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cki059bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":488};
const content = `<path class="cki059bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mixx" /></template>
