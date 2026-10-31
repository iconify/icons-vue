<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9pf8_h-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9pf8_h-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-fill-round" /></template>
