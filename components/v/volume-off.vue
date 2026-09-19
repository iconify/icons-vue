<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfz-e7d_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="cfz-e7d_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:volume-off" /></template>
