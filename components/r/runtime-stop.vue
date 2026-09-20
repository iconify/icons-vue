<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-s5qb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mf-s5qb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:runtime-stop" /></template>
