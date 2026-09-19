<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecfa-38zj.css';
import '../../css/a/awir01b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ecfa-38zj"/><path class="awir01b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:satisfy-definition" /></template>
