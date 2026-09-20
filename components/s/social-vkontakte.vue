<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i93c3tbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i93c3tbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-vkontakte" /></template>
