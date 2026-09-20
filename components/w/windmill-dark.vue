<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-0y0ftzh.css';
import '../../css/q/q-dq2zato.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-0y0ftzh"/><path class="q-dq2zato"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windmill-dark" /></template>
