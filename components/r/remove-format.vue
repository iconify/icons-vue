<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aksvw8bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aksvw8bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:remove-format" /></template>
