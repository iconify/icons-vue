<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywgnk_p2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ywgnk_p2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nxs" /></template>
