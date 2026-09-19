<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt10hccok.css';
import '../../css/z/z_2v24bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="yt10hccok"/><path class="z_2v24bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:walk" /></template>
