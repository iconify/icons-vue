<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wswvxk1sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wswvxk1sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:xbox-remix" /></template>
