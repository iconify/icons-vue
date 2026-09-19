<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc9qv4tax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rc9qv4tax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:triangle-outline" /></template>
