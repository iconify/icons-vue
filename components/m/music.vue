<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrrmz9eas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nrrmz9eas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:music" /></template>
