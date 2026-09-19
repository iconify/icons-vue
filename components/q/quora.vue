<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhemwg1as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rhemwg1as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:quora" /></template>
