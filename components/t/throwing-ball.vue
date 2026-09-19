<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1t09u-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qw1t09u-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:throwing-ball" /></template>
