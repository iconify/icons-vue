<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcm2tjbsz.css';
import '../../css/d/dz7650h2w.css';
import '../../css/u/uol8h3pbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcm2tjbsz"/><path clip-rule="evenodd" class="dz7650h2w"/><path class="uol8h3pbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sparks-off" /></template>
