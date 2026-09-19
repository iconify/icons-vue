<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo41xfbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uo41xfbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:path" /></template>
