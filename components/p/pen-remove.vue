<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gebnwiepn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gebnwiepn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pen-remove" /></template>
