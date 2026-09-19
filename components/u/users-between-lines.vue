<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0h6gbipf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s0h6gbipf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:users-between-lines" /></template>
