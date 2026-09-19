<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab10wbczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ab10wbczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:martini-glass" /></template>
