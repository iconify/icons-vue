<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1flx7vsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1flx7vsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:sort-up" /></template>
