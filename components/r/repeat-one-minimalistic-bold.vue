<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziumw9htl.css';
import '../../css/l/ltth4zvne.css';
import '../../css/t/t4p0zib2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziumw9htl"/><path clip-rule="evenodd" class="ltth4zvne"/><path class="t4p0zib2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-minimalistic-bold" /></template>
