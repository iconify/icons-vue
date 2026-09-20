<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsiur-b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsiur-b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:passing" /></template>
