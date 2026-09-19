<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al02msytu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="al02msytu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:youtube" /></template>
