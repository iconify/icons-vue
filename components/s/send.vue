<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixn7vnb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ixn7vnb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:send" /></template>
