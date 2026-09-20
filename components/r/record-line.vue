<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg5z4hbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg5z4hbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:record-line" /></template>
