<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah5v3fl3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ah5v3fl3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:repo-solid" /></template>
