<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgh4-s7mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgh4-s7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruble-outline" /></template>
