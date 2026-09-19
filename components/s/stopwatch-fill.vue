<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jusstw7zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jusstw7zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:stopwatch-fill" /></template>
