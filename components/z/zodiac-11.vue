<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvqxsz1-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rvqxsz1-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-11" /></template>
