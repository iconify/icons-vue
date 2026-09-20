<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tswncoo2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tswncoo2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-1-circle" /></template>
