<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uetza5byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uetza5byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:placemark-fill" /></template>
