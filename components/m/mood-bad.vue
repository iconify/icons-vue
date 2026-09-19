<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9r-peody.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="a9r-peody"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mood-bad" /></template>
