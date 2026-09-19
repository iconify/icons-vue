<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqdlc6agx.css';
import '../../css/e/e45bw9w1u.css';
import '../../css/r/r5_13j3mr.css';
import '../../css/s/sfhb73n1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqdlc6agx"/><path class="e45bw9w1u"/><path class="r5_13j3mr"/><path class="sfhb73n1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:windchime" /></template>
