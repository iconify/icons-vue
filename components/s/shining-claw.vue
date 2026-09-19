<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/benx3_b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="benx3_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shining-claw" /></template>
