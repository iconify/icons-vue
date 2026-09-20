<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk8z0l.css';
import '../../css/y/ydovum.css';
import '../../css/p/pde8iy.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk8z0l ydovum"/><circle class="pde8iy ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch-twotone" /></template>
