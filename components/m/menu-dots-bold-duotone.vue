<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxgoffwmm.css';
import '../../css/y/ywojd67ji.css';
import '../../css/k/khsdxy-1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxgoffwmm"/><path class="ywojd67ji"/><path class="khsdxy-1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-bold-duotone" /></template>
