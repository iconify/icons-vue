<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py-1lnuoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="py-1lnuoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pylon" /></template>
