<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwpdsu_nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwpdsu_nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:symptoms-nausea" /></template>
