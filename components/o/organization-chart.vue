<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdf_ixb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdf_ixb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:organization-chart" /></template>
