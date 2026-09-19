<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbr4szslo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="kbr4szslo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:microphone-alt" /></template>
