<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iggb9bb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iggb9bb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:signal-full-flat" /></template>
