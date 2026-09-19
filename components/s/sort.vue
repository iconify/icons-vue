<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ons7wnazk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":462,"height":698};
const content = `<path class="ons7wnazk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sort" /></template>
