<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-napbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps-napbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-square-minimalistic-outline" /></template>
