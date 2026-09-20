<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlg4kvbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlg4kvbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wall-fire" /></template>
