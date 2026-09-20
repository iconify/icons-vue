<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycln-b8i.css';
import '../../css/g/g4i_lk0zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="g4i_lk0zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamlresume" /></template>
