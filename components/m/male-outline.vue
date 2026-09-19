<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7mn_xgnv.css';
import '../../css/v/v2yyhhawr.css';
import '../../css/y/yjsg9j51b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="v2yyhhawr"/><path class="yjsg9j51b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:male-outline" /></template>
