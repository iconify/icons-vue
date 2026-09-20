<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u37ywac-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u37ywac-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-alpha-filled" /></template>
