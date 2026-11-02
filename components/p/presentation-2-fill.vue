<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0mwdubax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0mwdubax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-2-fill" /></template>
