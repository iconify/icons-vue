<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slu3g-y_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slu3g-y_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves-vertical" /></template>
