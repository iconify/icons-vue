<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3t8dlfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew3t8dlfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-3-filled" /></template>
