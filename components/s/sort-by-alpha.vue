<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r34chttoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r34chttoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-by-alpha" /></template>
