<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u45v42bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u45v42bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:model-s" /></template>
