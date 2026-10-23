<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkrn0cc1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkrn0cc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil-off" /></template>
