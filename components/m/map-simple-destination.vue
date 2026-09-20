<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p484ajszk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p484ajszk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-simple-destination" /></template>
