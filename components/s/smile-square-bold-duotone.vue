<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/c/c-hky-bnv.css';
import '../../css/v/vu18-_bab.css';
import '../../css/r/r2dvf4bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="c-hky-bnv"/><path class="vu18-_bab"/><path class="r2dvf4bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smile-square-bold-duotone" /></template>
