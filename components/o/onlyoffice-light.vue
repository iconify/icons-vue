<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1-d8oozv.css';
import '../../css/m/mas9rozrn.css';
import '../../css/i/i49k2acdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1-d8oozv"/><path class="mas9rozrn"/><path class="i49k2acdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onlyoffice-light" /></template>
