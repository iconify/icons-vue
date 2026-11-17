<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-hof9sdl.css';
import '../../css/r/rp-2d-muk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-hof9sdl"/><path class="rp-2d-muk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-up-right-enter-filled" /></template>
