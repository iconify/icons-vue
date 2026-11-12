<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqtotg3-l.css';
import '../../css/p/p9wzaub_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqtotg3-l"/><path class="p9wzaub_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t3-code" /></template>
