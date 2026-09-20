<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzn5jgaqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzn5jgaqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pirate" /></template>
