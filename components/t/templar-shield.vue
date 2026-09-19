<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkxyh8svy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rkxyh8svy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:templar-shield" /></template>
