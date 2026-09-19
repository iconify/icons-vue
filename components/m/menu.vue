<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7kqcoj9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":653};
const content = `<path class="v7kqcoj9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:menu" /></template>
