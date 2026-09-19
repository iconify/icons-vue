<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utsj4bcuc.css';
import '../../css/m/mprl4mbnb.css';
import '../../css/e/e8068gado.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="utsj4bcuc"/><circle class="mprl4mbnb"/><circle class="e8068gado"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:more" /></template>
