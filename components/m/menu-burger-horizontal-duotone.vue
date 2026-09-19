<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it2o87jea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it2o87jea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-horizontal-duotone" /></template>
