<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjvpp3bga.css';
import '../../css/d/dslthebzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjvpp3bga"/><circle class="dslthebzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:protondb" /></template>
