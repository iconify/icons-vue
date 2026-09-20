<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh6p_1bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dh6p_1bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-broadleaved" /></template>
