<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw2r6z41g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw2r6z41g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-check-line" /></template>
