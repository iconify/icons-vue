<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bynk47z_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bynk47z_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-entry-for-pedestrians" /></template>
