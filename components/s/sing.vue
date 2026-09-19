<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzx3rkyyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzx3rkyyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sing" /></template>
