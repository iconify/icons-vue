<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwc8sccak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwc8sccak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:mouse-pointer" /></template>
