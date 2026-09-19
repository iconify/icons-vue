<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5dlufbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s5dlufbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wallet-bold" /></template>
