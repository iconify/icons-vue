<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7wov4bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f7wov4bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:plumbing" /></template>
