<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f83mn_-hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f83mn_-hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:power-outlet-type-b-bold" /></template>
