<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvwio-8xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":645,"height":751};
const content = `<path class="gvwio-8xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:yelp" /></template>
