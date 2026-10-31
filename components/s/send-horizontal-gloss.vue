<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdt07-esp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdt07-esp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-gloss" /></template>
