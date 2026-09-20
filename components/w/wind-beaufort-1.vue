<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9i96qbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="s9i96qbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-1" /></template>
