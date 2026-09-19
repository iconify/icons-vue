<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi1fgqnbj.css';
import '../../css/f/fqpkdbsbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bi1fgqnbj"/><path class="fqpkdbsbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-add" /></template>
