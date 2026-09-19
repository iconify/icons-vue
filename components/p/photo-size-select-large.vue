<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acv8zdb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="acv8zdb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:photo-size-select-large" /></template>
