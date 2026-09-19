<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3r6n63fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3r6n63fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:phone" /></template>
