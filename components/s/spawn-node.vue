<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql7d5ob1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ql7d5ob1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spawn-node" /></template>
