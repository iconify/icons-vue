<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7tf-eb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x7tf-eb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:view-collapse" /></template>
