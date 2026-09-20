<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg-_6t7_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg-_6t7_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-code" /></template>
