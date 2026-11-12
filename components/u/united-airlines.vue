<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';
import '../../css/b/br3ht8bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="br3ht8bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:united-airlines" /></template>
