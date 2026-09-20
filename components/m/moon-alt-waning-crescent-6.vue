<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znuit7wvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="znuit7wvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-crescent-6" /></template>
