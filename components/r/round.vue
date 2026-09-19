<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjei4k8qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cjei4k8qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:round" /></template>
