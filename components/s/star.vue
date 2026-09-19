<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdamo78ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdamo78ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:star" /></template>
