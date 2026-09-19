<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7-z29e1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":640};
const content = `<path class="a7-z29e1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:paramater" /></template>
