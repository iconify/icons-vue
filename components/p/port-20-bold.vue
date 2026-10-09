<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poefxtbls.css';
import '../../css/a/alj1n3b0b.css';
import '../../css/z/zvh232b5d.css';
import '../../css/s/s9k_2uvrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="poefxtbls"/><path class="alj1n3b0b"/><path class="zvh232b5d"/><path class="s9k_2uvrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:port-20-bold" /></template>
