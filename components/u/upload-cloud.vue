<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4sth9bce.css';
import '../../css/k/kttmg1byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d4sth9bce"/><path class="kttmg1byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:upload-cloud" /></template>
