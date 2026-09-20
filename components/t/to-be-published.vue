<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq9pe6bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq9pe6bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:to-be-published" /></template>
