<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdp0fsn3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdp0fsn3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:udacity" /></template>
