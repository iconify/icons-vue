<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g86p7cczn.css';
import '../../css/e/eb847rttw.css';
import '../../css/d/d28pnkcvk.css';
import '../../css/h/hhonhdeix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g86p7cczn"/><path class="eb847rttw"/><path class="d28pnkcvk"/><path class="hhonhdeix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:roastedsweetpotato" /></template>
