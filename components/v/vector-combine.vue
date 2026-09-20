<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi2r8foaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2r8foaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-combine" /></template>
