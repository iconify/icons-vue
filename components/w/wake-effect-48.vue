<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_4l3dbra.css';
import '../../css/r/r5t_d6bdj.css';
import '../../css/m/m9x6imbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_4l3dbra"/><path class="r5t_d6bdj"/><path class="m9x6imbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wake-effect-48" /></template>
