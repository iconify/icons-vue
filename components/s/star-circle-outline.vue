<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0bta1xpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0bta1xpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-circle-outline" /></template>
