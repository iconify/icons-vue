<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej8rvisjq.css';
import '../../css/n/np34t097q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej8rvisjq"/><path class="np34t097q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mkdocs" /></template>
