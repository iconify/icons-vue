<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfk9sbw9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mfk9sbw9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-move-row-after" /></template>
