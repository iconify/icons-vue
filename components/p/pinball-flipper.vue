<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo09xl7mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oo09xl7mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pinball-flipper" /></template>
