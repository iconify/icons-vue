<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_2ocb6i.css';
import '../../css/z/z1wl8j83j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1_2ocb6i"/><path class="z1wl8j83j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qwik-light" /></template>
