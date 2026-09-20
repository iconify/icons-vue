<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8gg70jax.css';
import '../../css/i/ihap6s9si.css';
import '../../css/l/l0t3xkb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8gg70jax"/><path class="ihap6s9si"/><path clip-rule="evenodd" class="l0t3xkb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:voice-id-smartphone" /></template>
