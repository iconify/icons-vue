<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg5l5wb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg5l5wb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-cell" /></template>
