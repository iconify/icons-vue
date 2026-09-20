<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lofrdjd_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":362};
const content = `<path clip-rule="evenodd" class="lofrdjd_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whatsapp" /></template>
