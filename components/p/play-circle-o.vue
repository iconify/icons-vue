<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3ud-2ngi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="x3ud-2ngi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:play-circle-o" /></template>
