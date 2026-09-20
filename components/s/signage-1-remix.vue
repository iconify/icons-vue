<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la3e5vmdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="la3e5vmdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:signage-1-remix" /></template>
