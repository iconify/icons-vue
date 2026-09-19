<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9kdpbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="li9kdpbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plane-outline" /></template>
