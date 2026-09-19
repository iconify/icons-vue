<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npx6xjwmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="npx6xjwmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-square-fill" /></template>
