<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rydvi-yuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rydvi-yuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mf" /></template>
