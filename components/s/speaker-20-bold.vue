<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0xmcccfl.css';
import '../../css/r/r_8u_eb_k.css';
import '../../css/d/dy97t_1fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w0xmcccfl"/><path class="r_8u_eb_k"/><path class="dy97t_1fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speaker-20-bold" /></template>
