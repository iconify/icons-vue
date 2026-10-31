<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eop8onyec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eop8onyec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-fill-round" /></template>
