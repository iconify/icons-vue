<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogq3q-bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ogq3q-bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pressure" /></template>
