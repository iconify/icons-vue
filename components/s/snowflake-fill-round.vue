<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-hv9wb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-hv9wb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-fill-round" /></template>
