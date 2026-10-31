<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bozixybsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bozixybsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pill-fill-round" /></template>
