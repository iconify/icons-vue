<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6f84htr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gs6f84htr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rock-and-roll-hand-remix" /></template>
