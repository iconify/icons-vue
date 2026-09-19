<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyr4js4ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyr4js4ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snitch-quidditch-ball" /></template>
