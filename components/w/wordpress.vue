<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkmhukbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":704};
const content = `<path class="dkmhukbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:wordpress" /></template>
