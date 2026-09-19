<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htzosabxt.css';
import '../../css/r/rbd0bhbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="htzosabxt"/><path class="rbd0bhbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snorkel" /></template>
