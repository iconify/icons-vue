<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7vwor30z.css';
import '../../css/z/znp8eubox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7vwor30z"/><path class="znp8eubox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medassist" /></template>
