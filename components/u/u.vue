<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-fgz7vur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="i-fgz7vur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:u" /></template>
