<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyvei5bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvei5bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-dashed" /></template>
