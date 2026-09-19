<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjoe70b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjoe70b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mecha-head" /></template>
