<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj-9hxbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vj-9hxbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-router-remix" /></template>
