<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm86fbbey.css';
import '../../css/c/c6ug3vbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm86fbbey"/><path class="c6ug3vbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notifuse" /></template>
