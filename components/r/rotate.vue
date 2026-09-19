<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru-jr9b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ru-jr9b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rotate" /></template>
