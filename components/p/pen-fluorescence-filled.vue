<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvxghjukm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvxghjukm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pen-fluorescence-filled" /></template>
