<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry73exxue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry73exxue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:snapchat" /></template>
