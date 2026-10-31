<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmvh42bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmvh42bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-round" /></template>
