<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nha2ysi6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nha2ysi6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:near-protocol" /></template>
