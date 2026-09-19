<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll6m4rbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ll6m4rbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sacrificial-dagger" /></template>
