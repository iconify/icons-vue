<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxpu4qbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxpu4qbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:paper-plane" /></template>
