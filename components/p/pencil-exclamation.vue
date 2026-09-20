<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc8hf49pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc8hf49pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-exclamation" /></template>
