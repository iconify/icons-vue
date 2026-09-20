<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqw90dbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqw90dbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-right-filled" /></template>
