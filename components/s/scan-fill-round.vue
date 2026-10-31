<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-mop9bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-mop9bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-fill-round" /></template>
