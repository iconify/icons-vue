<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0d1hcbit.css';
import '../../css/u/u2n18rsfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0d1hcbit"/><path class="u2n18rsfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zoom" /></template>
