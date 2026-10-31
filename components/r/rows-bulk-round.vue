<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga99nhblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga99nhblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rows-bulk-round" /></template>
