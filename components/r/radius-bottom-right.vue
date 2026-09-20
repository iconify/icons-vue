<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi4wy58vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4wy58vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radius-bottom-right" /></template>
