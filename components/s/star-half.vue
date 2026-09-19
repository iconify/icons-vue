<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao1aycnpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ao1aycnpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:star-half" /></template>
