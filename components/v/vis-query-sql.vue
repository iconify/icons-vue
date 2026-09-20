<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8s6xvu0y.css';
import '../../css/c/cmb2wab2t.css';
import '../../css/g/g00s9kkvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="cmb2wab2t"/><path clip-rule="evenodd" class="g00s9kkvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-query-sql" /></template>
