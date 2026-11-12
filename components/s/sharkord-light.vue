<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iii3nbb6b.css';
import '../../css/s/sdij9c2vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iii3nbb6b"/><path class="sdij9c2vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sharkord-light" /></template>
