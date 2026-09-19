<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3si62x3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":551,"height":717};
const content = `<path class="f3si62x3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:unlock" /></template>
