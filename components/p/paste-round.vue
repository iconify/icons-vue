<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r04mx-bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r04mx-bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paste-round" /></template>
