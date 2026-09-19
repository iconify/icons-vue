<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxzz49brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jxzz49brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plague-doctor-profile" /></template>
