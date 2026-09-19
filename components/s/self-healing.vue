<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utsibk09e.css';
import '../../css/v/vke_idboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utsibk09e"/><path class="vke_idboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:self-healing" /></template>
