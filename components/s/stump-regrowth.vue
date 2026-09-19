<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbntfcwop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbntfcwop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stump-regrowth" /></template>
