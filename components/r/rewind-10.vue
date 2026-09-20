<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atjum7blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atjum7blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rewind-10" /></template>
