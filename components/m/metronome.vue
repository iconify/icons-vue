<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma3n16bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="ma3n16bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:metronome" /></template>
