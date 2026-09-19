<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0ipyvbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":336,"height":456};
const content = `<path class="b0ipyvbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:remote-control-alt" /></template>
