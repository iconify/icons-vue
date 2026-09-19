<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njb1albut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njb1albut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shark-jaws" /></template>
