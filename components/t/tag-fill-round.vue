<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le5ojcc3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le5ojcc3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-fill-round" /></template>
