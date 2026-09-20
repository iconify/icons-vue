<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8v7dbnf.css';
import '../../css/v/vqiudcbyw.css';
import '../../css/p/pv376mv6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ml8v7dbnf"/><path class="vqiudcbyw"/><circle class="pv376mv6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surmai" /></template>
