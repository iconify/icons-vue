<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyz-9xb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyz-9xb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-round" /></template>
