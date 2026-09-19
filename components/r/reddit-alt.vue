<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbxqegtus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kbxqegtus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:reddit-alt" /></template>
