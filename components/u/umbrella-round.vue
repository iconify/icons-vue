<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgqev5g_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgqev5g_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:umbrella-round" /></template>
