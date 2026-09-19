<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmga3btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":668};
const content = `<path class="lgmga3btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tag" /></template>
