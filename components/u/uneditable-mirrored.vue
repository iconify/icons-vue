<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2u_hlbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f2u_hlbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:uneditable-mirrored" /></template>
