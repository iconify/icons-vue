<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbamynsme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="gbamynsme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:store" /></template>
