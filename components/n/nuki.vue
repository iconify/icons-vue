<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv-43281c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv-43281c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nuki" /></template>
