<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxgoffwmm.css';
import '../../css/m/m5-5o8s_j.css';
import '../../css/y/ywojd67ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxgoffwmm"/><path class="m5-5o8s_j"/><path class="ywojd67ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-bold" /></template>
