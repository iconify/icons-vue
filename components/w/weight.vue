<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bukk-sy7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bukk-sy7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:weight" /></template>
