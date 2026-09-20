<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3t3gjbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b3t3gjbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:railway-track-crossing-dashed-line" /></template>
