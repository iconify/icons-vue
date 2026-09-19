<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcye5bblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qcye5bblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modsine" /></template>
