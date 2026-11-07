<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_m1grh8p.css';
import '../../css/j/jdaorxbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_m1grh8p"/><path class="jdaorxbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-round-bold-duotone" /></template>
