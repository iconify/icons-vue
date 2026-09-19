<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoenl6jag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aoenl6jag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tkn" /></template>
