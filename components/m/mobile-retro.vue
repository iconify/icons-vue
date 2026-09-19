<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs5km1oqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="vs5km1oqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mobile-retro" /></template>
