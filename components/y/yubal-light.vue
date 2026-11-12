<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jokm5q72l.css';
import '../../css/u/uf6zebb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="jokm5q72l"/><path class="uf6zebb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yubal-light" /></template>
