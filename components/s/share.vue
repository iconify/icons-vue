<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awks9rbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="awks9rbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:share" /></template>
