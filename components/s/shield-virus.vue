<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dokbrr4ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dokbrr4ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shield-virus" /></template>
