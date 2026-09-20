<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh6rurf5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oh6rurf5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-1-remix" /></template>
