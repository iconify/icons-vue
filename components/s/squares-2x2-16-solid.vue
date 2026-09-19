<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqls33b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gqls33b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-2x2-16-solid" /></template>
