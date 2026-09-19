<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alr3ezbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alr3ezbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:two-handed-sword" /></template>
