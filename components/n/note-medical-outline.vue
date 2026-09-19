<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jz9srl9wp.css';
import '../../css/h/h0op-rznz.css';
import '../../css/a/a1ulxtbht.css';
import '../../css/q/qhecqmane.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jz9srl9wp"/><path class="h0op-rznz"/><path class="a1ulxtbht"/><path class="qhecqmane"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-medical-outline" /></template>
