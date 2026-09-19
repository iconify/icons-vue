<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py4q2dbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="py4q2dbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tag-more" /></template>
