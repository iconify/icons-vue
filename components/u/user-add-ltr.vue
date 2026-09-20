<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vftgk3iha.css';
import '../../css/c/chmm2dpgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vftgk3iha"/><circle class="chmm2dpgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-add-ltr" /></template>
