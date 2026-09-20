<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p37056bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p37056bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:tool-box" /></template>
