<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm3d29h0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm3d29h0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pen-add" /></template>
