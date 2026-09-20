<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk9_32boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vk9_32boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-logging-filled" /></template>
