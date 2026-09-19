<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-157z73m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="x-157z73m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-vimeo" /></template>
