<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9wvigyoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9wvigyoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-outline" /></template>
