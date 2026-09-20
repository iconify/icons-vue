<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_d_m5bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_d_m5bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vscodium" /></template>
