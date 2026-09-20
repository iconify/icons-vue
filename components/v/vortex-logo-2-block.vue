<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt5w84_se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt5w84_se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vortex-logo-2-block" /></template>
