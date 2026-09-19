<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajxg0wh-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ajxg0wh-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:stq" /></template>
