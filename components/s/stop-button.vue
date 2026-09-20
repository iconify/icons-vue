<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-f53ebvb.css';
import '../../css/r/r8o5bwx5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<rect class="z-f53ebvb"/><path class="r8o5bwx5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stop-button" /></template>
