<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw0cxs7kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nw0cxs7kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:windmill" /></template>
