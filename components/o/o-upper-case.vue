<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1s4i0cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":794,"height":775};
const content = `<path class="fw1s4i0cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:o-upper-case" /></template>
