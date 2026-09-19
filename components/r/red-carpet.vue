<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oorxl8bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oorxl8bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:red-carpet" /></template>
