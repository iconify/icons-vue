<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xct43n9vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xct43n9vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:up-round" /></template>
