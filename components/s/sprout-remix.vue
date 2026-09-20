<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip9qdkb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ip9qdkb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sprout-remix" /></template>
