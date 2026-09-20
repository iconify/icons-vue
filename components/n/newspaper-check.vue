<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le9dz2kqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le9dz2kqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper-check" /></template>
