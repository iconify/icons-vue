<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz_-kvbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":656};
const content = `<path class="oz_-kvbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:reply" /></template>
