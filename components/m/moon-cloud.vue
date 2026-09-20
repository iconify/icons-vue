<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5nx4b1te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5nx4b1te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:moon-cloud" /></template>
