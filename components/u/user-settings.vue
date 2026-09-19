<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdii7hb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdii7hb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-settings" /></template>
