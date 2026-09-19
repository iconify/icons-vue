<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otv6zerrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="otv6zerrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:record-stroke-16" /></template>
