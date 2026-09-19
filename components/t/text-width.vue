<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf5_5ebiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="sf5_5ebiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:text-width" /></template>
