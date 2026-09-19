<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcg1trb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcg1trb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:text-align-left" /></template>
