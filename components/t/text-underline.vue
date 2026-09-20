<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxjcc1i8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zxjcc1i8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-underline" /></template>
