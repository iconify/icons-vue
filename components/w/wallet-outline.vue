<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d-kr02b7y.css';
import '../../css/g/g60wxkb7c.css';
import '../../css/t/tyixz-8qm.css';
import '../../css/i/i02qshb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d-kr02b7y"/><path class="g60wxkb7c"/><path class="tyixz-8qm"/><path class="i02qshb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wallet-outline" /></template>
