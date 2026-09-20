<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9iaqjb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9iaqjb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-cancel" /></template>
