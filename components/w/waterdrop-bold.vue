<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh1f_ub2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nh1f_ub2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:waterdrop-bold" /></template>
