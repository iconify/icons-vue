<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-8k04oul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-8k04oul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:port" /></template>
