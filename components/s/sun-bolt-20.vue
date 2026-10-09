<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciy5fzbxp.css';
import '../../css/a/apq2fzbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ciy5fzbxp"/><path class="apq2fzbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-bolt-20" /></template>
