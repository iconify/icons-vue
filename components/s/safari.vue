<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onq6dtr8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="onq6dtr8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:safari" /></template>
