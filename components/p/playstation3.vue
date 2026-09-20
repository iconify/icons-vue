<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on0yoobms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on0yoobms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playstation3" /></template>
