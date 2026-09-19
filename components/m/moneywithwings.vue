<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ece_obukg.css';
import '../../css/d/d-c_9e2ou.css';
import '../../css/x/x3lv_0s-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ece_obukg"/><path class="d-c_9e2ou"/><path class="x3lv_0s-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:moneywithwings" /></template>
