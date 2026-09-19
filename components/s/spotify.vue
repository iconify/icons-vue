<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnovelz4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="hnovelz4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:spotify" /></template>
