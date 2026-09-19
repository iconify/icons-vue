<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/secm1-tlc.css';
import '../../css/o/ozzrz2p5p.css';
import '../../css/v/v_3i9wmxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secm1-tlc"/><path class="ozzrz2p5p"/><path class="v_3i9wmxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:windows" /></template>
