<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otfv3cb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otfv3cb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sharp-halberd" /></template>
