<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxgt88b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxgt88b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tuning4-filled" /></template>
