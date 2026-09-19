<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd9r3qbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cd9r3qbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:repv2" /></template>
