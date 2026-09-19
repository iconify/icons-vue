<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksgi1ebim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksgi1ebim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stick-frame" /></template>
