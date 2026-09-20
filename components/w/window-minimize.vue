<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eemv9t5oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eemv9t5oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:window-minimize" /></template>
