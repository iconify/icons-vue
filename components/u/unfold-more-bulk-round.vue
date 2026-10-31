<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4v5_yb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4v5_yb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:unfold-more-bulk-round" /></template>
