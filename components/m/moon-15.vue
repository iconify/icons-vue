<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onxs8sd7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="onxs8sd7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-15" /></template>
