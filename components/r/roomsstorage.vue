<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0en2k76l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0en2k76l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsstorage" /></template>
