<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5q-ddpsz.css';
import '../../css/o/owf76acqr.css';
import '../../css/f/fgynpdb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5q-ddpsz"/><path class="owf76acqr"/><path clip-rule="evenodd" class="fgynpdb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tornado-bold" /></template>
