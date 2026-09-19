<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv3n7ebil.css';
import '../../css/f/f--feebbp.css';
import '../../css/a/abtx30h0p.css';
import '../../css/k/kd7vgqb6g.css';
import '../../css/o/ogs17-uwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kv3n7ebil"/><path class="f--feebbp"/><path class="abtx30h0p"/><path class="kd7vgqb6g"/><path class="ogs17-uwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:woocommerce-wordmark" /></template>
