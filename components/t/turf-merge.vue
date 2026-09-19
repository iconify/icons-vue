<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de_bqeb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="de_bqeb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-merge" /></template>
