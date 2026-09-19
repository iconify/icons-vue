<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/appt62b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="appt62b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkles-1" /></template>
