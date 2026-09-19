<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mddf--b2d.css';
import '../../css/k/k3s0atbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mddf--b2d"/><path class="k3s0atbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:quasar-wordmark" /></template>
