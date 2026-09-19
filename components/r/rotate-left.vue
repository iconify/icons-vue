<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsl99zbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsl99zbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rotate-left" /></template>
