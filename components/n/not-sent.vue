<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do95htb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="do95htb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:not-sent" /></template>
