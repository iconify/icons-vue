<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcxrfpb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcxrfpb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-right-bold" /></template>
