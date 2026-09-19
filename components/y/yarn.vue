<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm0c7-bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cm0c7-bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:yarn" /></template>
