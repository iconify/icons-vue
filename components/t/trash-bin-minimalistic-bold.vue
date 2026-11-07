<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3n43-bnv.css';
import '../../css/t/tjg1izbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n43-bnv"/><path clip-rule="evenodd" class="tjg1izbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-bold" /></template>
