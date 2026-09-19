<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijb5hobhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ijb5hobhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-vertical-alignment" /></template>
