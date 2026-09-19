<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2qpr6-4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2112,"height":1920};
const content = `<path class="l2qpr6-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:party" /></template>
