<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te04s0bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":733};
const content = `<path class="te04s0bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:repeat" /></template>
