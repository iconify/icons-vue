<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aik43r5pi.css';
import '../../css/d/dl12cln-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aik43r5pi"/><path class="dl12cln-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-settings" /></template>
