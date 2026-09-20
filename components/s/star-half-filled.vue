<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vks6qxb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vks6qxb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-half-filled" /></template>
