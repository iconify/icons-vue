<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-9gbzbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-9gbzbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speaker-2-line" /></template>
