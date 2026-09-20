<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g36zgr.css';
import '../../css/m/mux-7n.css';
import '../../css/c/cx-from-17px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g36zgr"/><circle class="mux-7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch-to-switch-off-transition" /></template>
