<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni3s1zbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ni3s1zbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mercury" /></template>
