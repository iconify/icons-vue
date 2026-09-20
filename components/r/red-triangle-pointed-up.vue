<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo1g7xbzh.css';
import '../../css/y/yvaz16bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zo1g7xbzh"/><path class="yvaz16bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:red-triangle-pointed-up" /></template>
