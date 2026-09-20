<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx__3hi9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lx__3hi9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-2-outline" /></template>
