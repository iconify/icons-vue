<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak7eg6csd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak7eg6csd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receive-square2-filled" /></template>
