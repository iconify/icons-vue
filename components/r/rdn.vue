<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aue3nn3gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aue3nn3gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rdn" /></template>
