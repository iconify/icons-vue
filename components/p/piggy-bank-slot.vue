<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw-8qhb8k.css';
import '../../css/a/a78cr7b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lw-8qhb8k"/><path class="a78cr7b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:piggy-bank-slot" /></template>
