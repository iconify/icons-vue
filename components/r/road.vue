<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl33snbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rl33snbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:road" /></template>
