<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjc_zt5-d.css';
import '../../css/c/cr5oxtb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjc_zt5-d"/><path class="cr5oxtb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ups" /></template>
