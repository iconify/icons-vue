<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztyl-_j6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ztyl-_j6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:quantum-qpu" /></template>
