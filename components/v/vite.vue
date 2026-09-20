<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls9wmez3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ls9wmez3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vite" /></template>
