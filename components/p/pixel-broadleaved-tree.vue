<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nss30vccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nss30vccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-broadleaved-tree" /></template>
