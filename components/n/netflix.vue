<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1jpv0wuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1jpv0wuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:netflix" /></template>
