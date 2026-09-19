<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elu5rbx0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elu5rbx0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-three" /></template>
