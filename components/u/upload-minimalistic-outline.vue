<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urermcsco.css';
import '../../css/h/hjvg905kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urermcsco"/><path class="hjvg905kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-minimalistic-outline" /></template>
