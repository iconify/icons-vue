<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_6htbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh_6htbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-3-fill-round" /></template>
