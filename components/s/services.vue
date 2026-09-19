<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxfi2jb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jxfi2jb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:services" /></template>
