<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9v0nvb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9v0nvb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vampire-cape" /></template>
