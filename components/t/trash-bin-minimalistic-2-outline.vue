<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loc47zw8p.css';
import '../../css/f/fib6k6-vs.css';
import '../../css/q/q37ppubrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loc47zw8p"/><path class="fib6k6-vs"/><path class="q37ppubrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-2-outline" /></template>
