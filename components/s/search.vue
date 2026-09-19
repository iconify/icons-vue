<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxt_agb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxt_agb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:search" /></template>
