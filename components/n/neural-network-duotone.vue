<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1y8uidcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1y8uidcj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:neural-network-duotone" /></template>
