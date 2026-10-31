<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9g8vnx-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9g8vnx-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stop-bulk-round" /></template>
