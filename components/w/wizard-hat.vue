<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0lmd5bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0lmd5bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wizard-hat" /></template>
