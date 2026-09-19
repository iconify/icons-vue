<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hitnyjdkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="hitnyjdkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:up-down" /></template>
