<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_lt3l0cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e_lt3l0cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vnv" /></template>
