<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs9gu7n4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs9gu7n4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volume" /></template>
