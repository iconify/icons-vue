<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1bvnqfvt.css';
import '../../css/m/m4styj0nb.css';
import '../../css/m/mz1do-bvr.css';
import '../../css/q/q1sggqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1bvnqfvt"/><path class="m4styj0nb"/><path class="mz1do-bvr"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-circle-outline" /></template>
