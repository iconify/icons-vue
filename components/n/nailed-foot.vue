<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4tf1rnas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4tf1rnas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nailed-foot" /></template>
