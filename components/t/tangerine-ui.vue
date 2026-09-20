<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqb812bom.css';
import '../../css/p/ph6nbhfkp.css';
import '../../css/h/hgj6s0-wz.css';
import '../../css/b/bodq3cb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqb812bom"/><path class="ph6nbhfkp"/><path class="hgj6s0-wz"/><path class="bodq3cb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tangerine-ui" /></template>
