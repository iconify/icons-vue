<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfsbn3c_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfsbn3c_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:reolink-811" /></template>
