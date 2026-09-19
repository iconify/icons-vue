<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk6666kbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rk6666kbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:sold-out" /></template>
