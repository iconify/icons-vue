<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpy6vikpy.css';
import '../../css/z/zsv18cbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpy6vikpy"/><path clip-rule="evenodd" class="zsv18cbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-minimalistic-bold" /></template>
