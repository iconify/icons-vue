<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crrk-xbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crrk-xbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:tag" /></template>
