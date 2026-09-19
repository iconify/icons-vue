<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vugygd5du.css';
import '../../css/b/bjggiqboe.css';
import '../../css/f/faeazbblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vugygd5du"/><path class="bjggiqboe"/><path class="faeazbblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:poo" /></template>
