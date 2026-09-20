<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rean51pzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rean51pzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-light" /></template>
