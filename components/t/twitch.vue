<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8ghxccvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j8ghxccvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:twitch" /></template>
