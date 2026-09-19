<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzkfv2_pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzkfv2_pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:pause" /></template>
