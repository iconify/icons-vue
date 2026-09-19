<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic52moyir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="ic52moyir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:reddit" /></template>
