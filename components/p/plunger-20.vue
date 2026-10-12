<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbyoeqbxo.css';
import '../../css/v/vp_3b7bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kbyoeqbxo"/><path class="vp_3b7bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plunger-20" /></template>
