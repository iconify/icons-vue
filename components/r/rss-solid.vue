<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esk15tbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="esk15tbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rss-solid" /></template>
