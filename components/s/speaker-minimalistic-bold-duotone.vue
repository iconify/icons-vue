<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke4nxkbkt.css';
import '../../css/c/cj76tkanc.css';
import '../../css/n/n2gzn3bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke4nxkbkt"/><path class="cj76tkanc"/><path clip-rule="evenodd" class="n2gzn3bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-minimalistic-bold-duotone" /></template>
