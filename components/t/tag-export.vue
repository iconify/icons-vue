<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k87mgcena.css';
import '../../css/h/hwg0k-kmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k87mgcena"/><path class="hwg0k-kmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag-export" /></template>
