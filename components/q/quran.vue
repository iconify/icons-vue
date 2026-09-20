<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6uw3rb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n6uw3rb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:quran" /></template>
