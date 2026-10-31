<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp7w3xhkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7w3xhkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scooter-fill-round" /></template>
