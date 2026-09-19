<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwghp2zfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwghp2zfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trophies-shelf" /></template>
