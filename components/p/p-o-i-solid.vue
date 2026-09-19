<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdt66ccyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gdt66ccyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:p-o-i-solid" /></template>
