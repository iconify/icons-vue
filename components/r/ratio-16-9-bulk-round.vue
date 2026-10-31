<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f932xy51a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f932xy51a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-16-9-bulk-round" /></template>
