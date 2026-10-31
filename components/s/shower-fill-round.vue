<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phii_pblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phii_pblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shower-fill-round" /></template>
