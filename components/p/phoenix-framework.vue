<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu34v8bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nu34v8bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:phoenix-framework" /></template>
