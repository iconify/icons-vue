<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0vk71j4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0vk71j4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:robber-mask" /></template>
