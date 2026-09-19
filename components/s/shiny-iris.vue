<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7lq-ab2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7lq-ab2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shiny-iris" /></template>
