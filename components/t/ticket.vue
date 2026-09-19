<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tth_cmy-p.css';
import '../../css/a/agi54rj7k.css';
import '../../css/j/jsp36ebok.css';
import '../../css/d/d94gehbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tth_cmy-p"/><path class="agi54rj7k"/><path class="jsp36ebok"/><path class="d94gehbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ticket" /></template>
