<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_1agk52v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_1agk52v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:multi-directions" /></template>
