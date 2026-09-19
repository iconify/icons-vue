<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq-j5olxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="vq-j5olxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:uniregistry" /></template>
