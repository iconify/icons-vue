<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzj27ikwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzj27ikwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-bezier-arc" /></template>
