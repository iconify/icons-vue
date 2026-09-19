<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buisi0gzo.css';
import '../../css/f/fvsrkp2dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="buisi0gzo"/><path class="fvsrkp2dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:school" /></template>
