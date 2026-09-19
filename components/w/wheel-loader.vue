<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kicchf92z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kicchf92z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wheel-loader" /></template>
