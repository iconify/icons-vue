<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmdg2lbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="gmdg2lbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-9" /></template>
