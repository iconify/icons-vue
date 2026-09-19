<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3mya35-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l3mya35-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-forward-filled" /></template>
