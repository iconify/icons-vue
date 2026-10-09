<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg3i25mms.css';
import '../../css/u/u80q53cnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tg3i25mms"/><path class="u80q53cnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-data-20" /></template>
