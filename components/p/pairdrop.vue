<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3c4wab0s.css';
import '../../css/a/ay474ak4m.css';
import '../../css/h/h-9zx8bmp.css';
import '../../css/v/vnutggnhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3c4wab0s"/><path class="ay474ak4m"/><path class="h-9zx8bmp"/><path class="vnutggnhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pairdrop" /></template>
