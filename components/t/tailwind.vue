<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8_g_z5oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8_g_z5oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tailwind" /></template>
