<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuallir8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuallir8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:thread-net" /></template>
