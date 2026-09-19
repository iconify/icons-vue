<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh0aorlcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bh0aorlcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:pause" /></template>
