<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc5busrsc.css';
import '../../css/o/oim_e1bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc5busrsc"/><path class="oim_e1bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:save-fill" /></template>
