<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9w22fbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9w22fbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wok" /></template>
