<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv5v4ubor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kv5v4ubor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:marginal" /></template>
