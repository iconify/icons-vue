<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cysjv4btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cysjv4btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:question-mark-circle-fill-20" /></template>
