<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc-s60n_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fc-s60n_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-square-fill" /></template>
