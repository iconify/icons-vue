<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9mv4w0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co9mv4w0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:purple-square" /></template>
