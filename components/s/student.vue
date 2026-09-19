<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axeen7-9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="axeen7-9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:student" /></template>
