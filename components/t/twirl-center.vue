<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz4bcds_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bz4bcds_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:twirl-center" /></template>
