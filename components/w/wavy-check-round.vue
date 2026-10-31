<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grxn4ab8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grxn4ab8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-check-round" /></template>
