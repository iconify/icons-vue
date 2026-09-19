<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwt473w_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwt473w_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:raining" /></template>
