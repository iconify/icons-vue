<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjuucw99j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjuucw99j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:riot-shield" /></template>
