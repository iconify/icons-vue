<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbn-w6b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbn-w6b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:squares-2x2-expressive" /></template>
