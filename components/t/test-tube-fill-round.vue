<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u07sl8b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u07sl8b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:test-tube-fill-round" /></template>
