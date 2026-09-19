<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqapy4bsh.css';
import '../../css/u/uy44wxbxz.css';
import '../../css/n/n230x8b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iqapy4bsh"/><path class="uy44wxbxz"/><path class="n230x8b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackoverflow-wordmark" /></template>
