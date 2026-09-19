<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7wdk6bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s7wdk6bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:ticket" /></template>
