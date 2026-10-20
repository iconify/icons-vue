<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vttjpyben.css';
import '../../css/c/c4mkapibv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vttjpyben"/><path class="c4mkapibv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-sparkle-20-bold" /></template>
