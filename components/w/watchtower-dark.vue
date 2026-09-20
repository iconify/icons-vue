<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2q-obza.css';
import '../../css/s/s_1q0sbix.css';
import '../../css/w/w37xe3b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud2q-obza"/><path class="s_1q0sbix"/><path class="w37xe3b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchtower-dark" /></template>
