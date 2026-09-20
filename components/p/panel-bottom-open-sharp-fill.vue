<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw50-2a5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw50-2a5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open-sharp-fill" /></template>
