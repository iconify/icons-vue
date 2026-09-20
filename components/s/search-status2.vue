<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzpy-2vtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzpy-2vtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-status2" /></template>
