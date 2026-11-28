<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn6kclv_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn6kclv_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-search" /></template>
