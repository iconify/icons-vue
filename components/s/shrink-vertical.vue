<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmjzb8d8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmjzb8d8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shrink-vertical" /></template>
