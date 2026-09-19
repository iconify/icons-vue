<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y_4x41bif.css';
import '../../css/f/fh-vz5swt.css';
import '../../css/r/r-77_6bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y_4x41bif"/><rect class="fh-vz5swt"/><path class="r-77_6bxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:mic-check" /></template>
