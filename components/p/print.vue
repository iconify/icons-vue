<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwj3zabgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lwj3zabgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:print" /></template>
