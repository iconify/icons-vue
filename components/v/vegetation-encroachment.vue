<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv88c2lwy.css';
import '../../css/e/ezwpo0b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nv88c2lwy"/><path class="ezwpo0b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vegetation-encroachment" /></template>
