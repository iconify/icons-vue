<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-357n8kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-357n8kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:popcorn-solid" /></template>
