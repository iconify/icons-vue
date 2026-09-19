<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfppcshjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfppcshjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:waste" /></template>
