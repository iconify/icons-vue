<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fgh801jof.css';
import '../../css/k/kkl3fjb8n.css';
import '../../css/l/lq4d5ranb.css';
import '../../css/n/n7qjv3z9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fgh801jof"/><path class="kkl3fjb8n"/><path class="lq4d5ranb"/><path class="n7qjv3z9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:users-1-outline" /></template>
