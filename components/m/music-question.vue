<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nriz88b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nriz88b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-question" /></template>
