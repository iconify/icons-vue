<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3pjvc4ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3pjvc4ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stack-exchange" /></template>
