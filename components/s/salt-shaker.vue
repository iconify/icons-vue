<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhm1_nbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhm1_nbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:salt-shaker" /></template>
