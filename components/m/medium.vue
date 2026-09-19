<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1gfmgbwj.css';
import '../../css/z/z_i6pn2af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1gfmgbwj"/><path class="z_i6pn2af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:medium" /></template>
