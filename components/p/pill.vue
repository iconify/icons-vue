<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb9z1ab3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bb9z1ab3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:pill" /></template>
