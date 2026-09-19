<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg21660si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zg21660si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oil-rig" /></template>
