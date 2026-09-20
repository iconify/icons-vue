<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4d_gbb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n4d_gbb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:window" /></template>
