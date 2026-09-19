<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgxkfjd6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgxkfjd6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti" /></template>
