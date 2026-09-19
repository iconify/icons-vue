<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsh3n7vpt.css';
import '../../css/n/npoomsb7x.css';
import '../../css/s/sg68hbv5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="nsh3n7vpt"/><path class="npoomsb7x"/><path class="sg68hbv5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wifi" /></template>
