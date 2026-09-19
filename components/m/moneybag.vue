<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxnzi-byq.css';
import '../../css/d/dmwskda3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxnzi-byq"/><path class="dmwskda3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:moneybag" /></template>
