<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0119acpd.css';
import '../../css/c/cj-ip0b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0119acpd"/><path class="cj-ip0b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:row-delete" /></template>
