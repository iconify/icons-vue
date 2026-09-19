<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi0ggj54w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vi0ggj54w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user" /></template>
