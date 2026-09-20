<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj_-cngib.css';
import '../../css/z/z-izombsf.css';
import '../../css/b/b9755ib4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj_-cngib"/><path class="z-izombsf"/><path class="b9755ib4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postgresql" /></template>
