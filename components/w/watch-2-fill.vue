<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs8yrvbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs8yrvbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watch-2-fill" /></template>
