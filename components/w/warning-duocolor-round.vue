<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijx--jbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijx--jbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warning-duocolor-round" /></template>
