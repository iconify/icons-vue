<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4wea34zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4wea34zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pimiento" /></template>
