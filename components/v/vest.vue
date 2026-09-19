<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nphgnebzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nphgnebzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:vest" /></template>
