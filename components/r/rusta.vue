<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltgkmpbdc.css';
import '../../css/f/flakb15jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltgkmpbdc"/><path class="flakb15jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rusta" /></template>
