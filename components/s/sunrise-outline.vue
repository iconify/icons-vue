<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y7nwf97xa.css';
import '../../css/p/p_lzu_bcm.css';
import '../../css/o/ovbjaibzx.css';
import '../../css/a/avzl_8b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y7nwf97xa"/><path class="p_lzu_bcm"/><path class="ovbjaibzx"/><path class="avzl_8b-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunrise-outline" /></template>
