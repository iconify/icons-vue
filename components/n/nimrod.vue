<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6unurbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g6unurbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nimrod" /></template>
