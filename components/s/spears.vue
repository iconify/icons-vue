<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g270unitk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g270unitk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spears" /></template>
