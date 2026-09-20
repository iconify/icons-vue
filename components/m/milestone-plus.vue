<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne-y8d_hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne-y8d_hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:milestone-plus" /></template>
