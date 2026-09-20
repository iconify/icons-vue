<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cec67vb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cec67vb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-alphabetical-ascending-variant" /></template>
