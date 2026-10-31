<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urv1w5b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urv1w5b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-sparkle-round" /></template>
