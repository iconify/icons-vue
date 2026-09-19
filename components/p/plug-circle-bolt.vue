<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otfun1b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="otfun1b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plug-circle-bolt" /></template>
