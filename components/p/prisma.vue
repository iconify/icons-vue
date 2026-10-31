<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irmk_pbcb.css';
import '../../css/z/zpt2lgb4a.css';
import '../../css/r/rpp_nsbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="irmk_pbcb"/><path class="zpt2lgb4a"/><path class="rpp_nsbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:prisma" /></template>
