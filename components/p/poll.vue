<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-7kqbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-7kqbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:poll" /></template>
