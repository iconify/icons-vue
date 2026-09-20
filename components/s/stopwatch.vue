<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aac4duxdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aac4duxdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stopwatch" /></template>
