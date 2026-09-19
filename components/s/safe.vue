<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwf_e237l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwf_e237l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:safe" /></template>
