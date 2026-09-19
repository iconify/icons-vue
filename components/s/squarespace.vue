<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6jk8epgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s6jk8epgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:squarespace" /></template>
