<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-lmr9bkb.css';
import '../../css/t/tk7jp-bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z-lmr9bkb"/><path class="tk7jp-bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subsea-cable-20-bold" /></template>
