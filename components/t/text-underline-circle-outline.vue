<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9tzwj7ok.css';
import '../../css/b/bzy5eobti.css';
import '../../css/f/fhxzx1b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9tzwj7ok"/><path class="bzy5eobti"/><path clip-rule="evenodd" class="fhxzx1b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-circle-outline" /></template>
