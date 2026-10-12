<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du1wh4bdg.css';
import '../../css/s/s26wu4bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du1wh4bdg"/><path class="s26wu4bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-arrow-left-filled" /></template>
