<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maf_-rbzb.css';
import '../../css/k/keeeh295c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maf_-rbzb"/><path class="keeeh295c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:paint-roll" /></template>
