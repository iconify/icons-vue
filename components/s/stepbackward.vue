<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dksr4sbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="dksr4sbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stepbackward" /></template>
