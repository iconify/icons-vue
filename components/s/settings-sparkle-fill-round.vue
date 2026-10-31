<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r602s8bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r602s8bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-sparkle-fill-round" /></template>
