<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asxgz14_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asxgz14_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:toothbrush" /></template>
