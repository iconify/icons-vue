<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0z_iih3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0z_iih3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:power-cycle" /></template>
