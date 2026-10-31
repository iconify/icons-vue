<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep8-spb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8-spb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:refresh-gloss" /></template>
