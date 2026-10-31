<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfbjdmbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbjdmbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-cursor-gloss" /></template>
