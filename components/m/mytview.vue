<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maehpb1hl.css';
import '../../css/o/ouy5zcixh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="maehpb1hl"/><path class="ouy5zcixh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mytview" /></template>
