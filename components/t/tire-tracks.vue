<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhknmdhlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhknmdhlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tire-tracks" /></template>
