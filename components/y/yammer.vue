<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqwmy0b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tqwmy0b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yammer" /></template>
