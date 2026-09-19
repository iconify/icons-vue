<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl_wadqxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cl_wadqxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mozilla-firefox" /></template>
