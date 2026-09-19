<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z785cyn3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z785cyn3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:verified-brand" /></template>
