<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cifs7mbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cifs7mbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tanzania" /></template>
