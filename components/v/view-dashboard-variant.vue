<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbnjyebwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbnjyebwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-dashboard-variant" /></template>
