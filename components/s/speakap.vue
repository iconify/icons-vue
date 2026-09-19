<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kur4tfbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kur4tfbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:speakap" /></template>
