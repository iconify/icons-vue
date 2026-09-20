<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by6m3gbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by6m3gbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:silverware-variant" /></template>
