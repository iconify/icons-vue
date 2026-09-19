<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onghurb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="onghurb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:yelp" /></template>
