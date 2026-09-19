<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z477j3bdr.css';
import '../../css/g/gno1t7swb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="z477j3bdr"/><path class="gno1t7swb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trash-bin" /></template>
