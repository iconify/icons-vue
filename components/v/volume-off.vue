<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj9rb1bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1280};
const content = `<path class="sj9rb1bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:volume-off" /></template>
