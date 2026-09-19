<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sne2qlnhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sne2qlnhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:post-stamp" /></template>
