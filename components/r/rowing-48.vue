<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pktuq_lkk.css';
import '../../css/n/n1bc5gv3h.css';
import '../../css/l/l-h20ibdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pktuq_lkk"/><path class="n1bc5gv3h"/><path class="l-h20ibdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rowing-48" /></template>
