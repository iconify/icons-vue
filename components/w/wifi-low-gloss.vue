<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udfo3xbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udfo3xbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-low-gloss" /></template>
