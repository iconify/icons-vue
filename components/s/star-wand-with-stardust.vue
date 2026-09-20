<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg0kydbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tg0kydbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-wand-with-stardust" /></template>
