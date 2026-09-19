<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdzm_ubkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdzm_ubkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pounce" /></template>
