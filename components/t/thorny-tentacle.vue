<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-gpt_b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-gpt_b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thorny-tentacle" /></template>
