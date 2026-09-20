<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdxzjnb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdxzjnb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:single-quotes-r" /></template>
