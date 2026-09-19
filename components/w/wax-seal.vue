<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwm54coxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwm54coxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wax-seal" /></template>
