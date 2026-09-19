<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6e1gm-ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c6e1gm-ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:trash" /></template>
