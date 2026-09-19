<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4ap6cvjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4ap6cvjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:usage-included-use-case" /></template>
