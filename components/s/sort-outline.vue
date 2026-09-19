<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsbuvlmzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbuvlmzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:sort-outline" /></template>
