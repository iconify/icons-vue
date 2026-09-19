<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qht09-59q.css';
import '../../css/a/ana62cbyy.css';
import '../../css/q/q4oxf2bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qht09-59q"/><path class="ana62cbyy"/><path class="q4oxf2bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:waningbibbousmoon" /></template>
