<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzf2d5c2n.css';
import '../../css/t/tox1-wblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wzf2d5c2n"/><path class="tox1-wblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wallet-20" /></template>
