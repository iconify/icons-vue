<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5vyqz5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5vyqz5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:timeline-view" /></template>
