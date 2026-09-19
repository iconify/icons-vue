<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql__uvuun.css';
import '../../css/m/m42qaacec.css';
import '../../css/p/pmct9tb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ql__uvuun"/><path class="m42qaacec"/><path class="pmct9tb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:musicalkeyboard" /></template>
