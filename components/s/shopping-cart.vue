<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsdwxr0qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsdwxr0qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shopping-cart" /></template>
