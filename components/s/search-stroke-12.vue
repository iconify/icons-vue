<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbb1_2bju.css';
import '../../css/w/w43j2ubna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="nbb1_2bju"/><path class="w43j2ubna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:search-stroke-12" /></template>
