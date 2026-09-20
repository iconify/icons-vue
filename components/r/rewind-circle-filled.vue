<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6410_bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u6410_bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind-circle-filled" /></template>
