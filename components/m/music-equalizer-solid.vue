<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td8wbxbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="td8wbxbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-equalizer-solid" /></template>
