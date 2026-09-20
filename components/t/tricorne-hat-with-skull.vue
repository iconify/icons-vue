<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nes77ph0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nes77ph0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tricorne-hat-with-skull" /></template>
