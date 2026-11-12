<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nim_7djxm.css';
import '../../css/g/gfuuvl7et.css';
import '../../css/f/fme3m9bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nim_7djxm"/><path class="gfuuvl7et"/><path class="fme3m9bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:registry-console-dark" /></template>
