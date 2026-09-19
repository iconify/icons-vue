<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7h66w8ve.css';
import '../../css/c/cwbr59xig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7h66w8ve"/><path class="cwbr59xig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subnet-acl-rules" /></template>
