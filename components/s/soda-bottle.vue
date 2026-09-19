<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5-epbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv5-epbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soda-bottle" /></template>
