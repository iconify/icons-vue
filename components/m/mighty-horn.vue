<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2bh_xjbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b2bh_xjbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mighty-horn" /></template>
