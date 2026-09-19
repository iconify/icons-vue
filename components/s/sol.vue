<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnf-kcvqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xnf-kcvqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sol" /></template>
