<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae2ur5upl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ae2ur5upl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wheelchair-solid" /></template>
