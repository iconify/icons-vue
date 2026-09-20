<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcp2bq36g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcp2bq36g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pinterest-line" /></template>
