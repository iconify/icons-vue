<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejl9ky0qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejl9ky0qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notification-off" /></template>
