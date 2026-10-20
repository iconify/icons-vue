<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzs5177np.css';
import '../../css/l/lgqt567fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="lgqt567fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-sparkle-20" /></template>
