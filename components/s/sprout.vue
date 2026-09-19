<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw5ulsk-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dw5ulsk-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sprout" /></template>
