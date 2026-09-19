<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz606i7re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hz606i7re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-axe" /></template>
