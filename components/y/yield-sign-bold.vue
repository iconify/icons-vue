<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghnb59b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ghnb59b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:yield-sign-bold" /></template>
