<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju1iq-4lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1iq-4lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:youtube-fill-round" /></template>
