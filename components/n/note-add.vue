<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3ke734ah.css';
import '../../css/z/zagwqcton.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3ke734ah"/><path class="zagwqcton"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:note-add" /></template>
