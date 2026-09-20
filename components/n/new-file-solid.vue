<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0b5x4exe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f0b5x4exe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-file-solid" /></template>
