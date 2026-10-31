<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4djyqd2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4djyqd2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-3-duotone-round" /></template>
