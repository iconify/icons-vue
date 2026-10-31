<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3d68xb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3d68xb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-check-round" /></template>
