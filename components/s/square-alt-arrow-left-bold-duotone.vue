<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1bfxqbht.css';
import '../../css/q/q_szi_b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bfxqbht"/><path class="q_szi_b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-alt-arrow-left-bold-duotone" /></template>
