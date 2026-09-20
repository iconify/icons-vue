<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z46h88boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z46h88boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyden-light" /></template>
