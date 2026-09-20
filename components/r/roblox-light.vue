<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycbzi7r9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ycbzi7r9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roblox-light" /></template>
