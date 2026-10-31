<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilreftvpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilreftvpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-diagonal-2-fill-round" /></template>
