<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufyq-fb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ufyq-fb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watch" /></template>
