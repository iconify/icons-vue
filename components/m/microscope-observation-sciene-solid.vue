<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/occ1h7r-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="occ1h7r-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:microscope-observation-sciene-solid" /></template>
