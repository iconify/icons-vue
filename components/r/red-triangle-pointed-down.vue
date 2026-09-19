<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4dv_dq0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h4dv_dq0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:red-triangle-pointed-down" /></template>
