<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_iigfb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b_iigfb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:voice-scan-2" /></template>
