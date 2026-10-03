<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db17s4j6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db17s4j6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pixelwatch" /></template>
