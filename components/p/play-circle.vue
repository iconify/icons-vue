<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4j_jjn9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4j_jjn9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:play-circle" /></template>
