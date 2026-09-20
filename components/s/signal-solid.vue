<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7vn6ac5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t7vn6ac5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:signal-solid" /></template>
