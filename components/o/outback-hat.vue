<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpu03_f-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpu03_f-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:outback-hat" /></template>
