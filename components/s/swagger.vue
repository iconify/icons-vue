<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgo-iub5k.css';
import '../../css/e/e46esu-mc.css';
import '../../css/a/ak8ip-b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mgo-iub5k"/><path class="e46esu-mc"/><path class="ak8ip-b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:swagger" /></template>
