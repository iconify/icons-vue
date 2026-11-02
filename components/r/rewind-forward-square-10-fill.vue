<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wodxxpkrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wodxxpkrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-10-fill" /></template>
