<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8owapquf.css';
import '../../css/n/n5dg8triv.css';
import '../../css/l/lz13cdsdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8owapquf"/><path class="n5dg8triv"/><path class="lz13cdsdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-verge-dark" /></template>
