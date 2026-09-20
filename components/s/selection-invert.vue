<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl-9vxerp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl-9vxerp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-invert" /></template>
