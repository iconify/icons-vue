<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_x4m8o5k.css';
import '../../css/s/sb9z2f5dz.css';
import '../../css/w/wjkmecbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_x4m8o5k"/><path class="sb9z2f5dz"/><path class="wjkmecbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tape-measure-20-bold" /></template>
