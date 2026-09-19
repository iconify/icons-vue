<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-0ypccvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-0ypccvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:scan-circle" /></template>
