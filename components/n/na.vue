<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo1il0bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lo1il0bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:na" /></template>
