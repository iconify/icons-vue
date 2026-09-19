<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1jo94x0n.css';
import '../../css/h/h1tlzyagf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1jo94x0n"/><path class="h1tlzyagf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-thumbs-down" /></template>
