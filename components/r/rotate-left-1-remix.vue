<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_r7z49s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hu_r7z49s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:rotate-left-1-remix" /></template>
