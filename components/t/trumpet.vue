<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2q5w7pwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2q5w7pwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trumpet" /></template>
