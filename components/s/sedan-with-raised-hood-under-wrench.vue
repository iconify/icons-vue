<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysq-5acba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ysq-5acba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-with-raised-hood-under-wrench" /></template>
