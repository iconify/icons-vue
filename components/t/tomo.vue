<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbf8mobbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbf8mobbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tomo" /></template>
