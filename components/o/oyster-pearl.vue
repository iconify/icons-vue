<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn0gn1b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jn0gn1b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oyster-pearl" /></template>
