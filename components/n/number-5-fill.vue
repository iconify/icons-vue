<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-rr4qaar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-rr4qaar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-fill" /></template>
