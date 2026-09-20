<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krtk5sbwi.css';
import '../../css/v/v3t2okbsb.css';
import '../../css/j/j54-d_09m.css';
import '../../css/g/ggglnib_b.css';
import '../../css/u/u0hxj2bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="krtk5sbwi"/><path class="v3t2okbsb"/><path class="j54-d_09m"/><path class="ggglnib_b"/><path class="u0hxj2bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:medication" /></template>
