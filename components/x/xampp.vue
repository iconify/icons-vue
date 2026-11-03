<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8a4m0b2a.css';
import '../../css/h/hjzkjwhbs.css';
import '../../css/p/poazbeb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k8a4m0b2a"/><path class="hjzkjwhbs"/><path class="poazbeb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:xampp" /></template>
