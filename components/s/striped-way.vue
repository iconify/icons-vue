<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4whe5bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m4whe5bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:striped-way" /></template>
