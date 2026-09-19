<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw0pbjl4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0pbjl4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-2x2" /></template>
