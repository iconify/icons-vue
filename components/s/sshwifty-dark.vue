<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctjzpmbpg.css';
import '../../css/r/ry3qkjbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctjzpmbpg"/><path class="ry3qkjbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sshwifty-dark" /></template>
