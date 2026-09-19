<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8lgtac7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t8lgtac7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table-built" /></template>
