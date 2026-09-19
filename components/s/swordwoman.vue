<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl3p7dbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl3p7dbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swordwoman" /></template>
