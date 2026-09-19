<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9q05gbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9q05gbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:modern-city" /></template>
