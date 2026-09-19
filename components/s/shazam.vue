<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9_-f5bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9_-f5bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:shazam" /></template>
