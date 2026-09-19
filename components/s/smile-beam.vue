<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuz9bmb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="yuz9bmb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:smile-beam" /></template>
