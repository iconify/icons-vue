<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs56q1bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qs56q1bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:toggle-on" /></template>
