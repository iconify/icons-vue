<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asc_5xb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="asc_5xb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:textcursor" /></template>
