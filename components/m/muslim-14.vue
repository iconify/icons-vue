<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjv5k8bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kjv5k8bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:muslim-14" /></template>
