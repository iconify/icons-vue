<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbm3ckrdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbm3ckrdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ticket-star-bold" /></template>
