<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4_kai7yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4_kai7yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stopwatch-filled" /></template>
