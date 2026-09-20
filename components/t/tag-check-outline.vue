<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luqa1acen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luqa1acen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-check-outline" /></template>
