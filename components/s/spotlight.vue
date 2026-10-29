<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f14kce5-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f14kce5-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:spotlight" /></template>
