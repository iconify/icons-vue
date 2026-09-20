<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nepuf8mxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nepuf8mxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:train" /></template>
