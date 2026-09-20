<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co5gvya4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co5gvya4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thumbs-up" /></template>
