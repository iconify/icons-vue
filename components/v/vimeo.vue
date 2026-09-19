<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td6uc1khz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":456};
const content = `<path class="td6uc1khz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:vimeo" /></template>
