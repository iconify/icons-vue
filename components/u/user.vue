<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwqanrbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="xwqanrbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:user" /></template>
