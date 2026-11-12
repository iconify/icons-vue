<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8nktzdut.css';
import '../../css/l/lcji6ciap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="f8nktzdut"/><path class="lcji6ciap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yubal-dark" /></template>
