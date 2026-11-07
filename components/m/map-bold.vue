<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc3rqc7_z.css';
import '../../css/a/a1_algbwn.css';
import '../../css/o/ogwim4gsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc3rqc7_z"/><path class="a1_algbwn"/><path class="ogwim4gsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-bold" /></template>
