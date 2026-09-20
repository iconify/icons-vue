<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6-2urb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="j6-2urb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-1" /></template>
