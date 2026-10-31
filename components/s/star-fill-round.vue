<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9z-d2ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9z-d2ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-fill-round" /></template>
