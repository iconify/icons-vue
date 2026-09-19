<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zojk7bbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zojk7bbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tongue" /></template>
