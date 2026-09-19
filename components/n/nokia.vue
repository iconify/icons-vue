<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n43rae_eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n43rae_eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nokia" /></template>
