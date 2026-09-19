<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axmrgv7yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="axmrgv7yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:network-wired" /></template>
