<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz36zmk8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz36zmk8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:playlist" /></template>
