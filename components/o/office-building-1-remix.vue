<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypdsrabgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ypdsrabgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:office-building-1-remix" /></template>
