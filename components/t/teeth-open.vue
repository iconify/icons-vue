<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iib28-19w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iib28-19w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:teeth-open" /></template>
