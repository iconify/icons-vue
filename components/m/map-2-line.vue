<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq73-t5vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq73-t5vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-2-line" /></template>
