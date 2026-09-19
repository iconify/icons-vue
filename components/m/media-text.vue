<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xehvr1f4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xehvr1f4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:media-text" /></template>
