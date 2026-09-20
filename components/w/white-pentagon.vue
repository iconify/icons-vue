<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg5idf3sf.css';
import '../../css/v/vtcohfdfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="gg5idf3sf"/><path class="vtcohfdfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-pentagon" /></template>
