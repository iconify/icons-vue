<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr12701qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mr12701qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pile-of-poo" /></template>
