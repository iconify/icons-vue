<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dygia2sgr.css';
import '../../css/h/hbuiv42xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dygia2sgr"/><path class="hbuiv42xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-previous-bold-duotone" /></template>
