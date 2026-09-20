<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb6ezbbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fb6ezbbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-outline" /></template>
