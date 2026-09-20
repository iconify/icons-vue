<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spikp7boj.css';
import '../../css/m/mxutx8bjy.css';
import '../../css/p/pvcdc057u.css';
import '../../css/m/m49a1tu-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spikp7boj"/><path class="mxutx8bjy"/><path class="pvcdc057u"/><path class="m49a1tu-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roundcube" /></template>
