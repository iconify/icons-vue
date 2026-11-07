<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjq2w1_ae.css';
import '../../css/s/s53by5bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjq2w1_ae"/><path clip-rule="evenodd" class="s53by5bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-wave-bold-duotone" /></template>
