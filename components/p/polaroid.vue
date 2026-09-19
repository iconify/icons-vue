<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8bm8_bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8bm8_bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:polaroid" /></template>
