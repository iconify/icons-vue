<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-37_lbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-37_lbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ontology" /></template>
