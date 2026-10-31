<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhe-mqb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhe-mqb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-check-corner-round" /></template>
