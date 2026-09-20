<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c16wjhrqn.css';
import '../../css/s/suncofbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c16wjhrqn"/><path class="suncofbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wifi-solid" /></template>
