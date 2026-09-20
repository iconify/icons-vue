<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh1x06b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eh1x06b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-wi-fi-off" /></template>
