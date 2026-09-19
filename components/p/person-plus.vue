<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nc0ss4key.css';
import '../../css/s/scuo7ib6n.css';
import '../../css/n/njqf7ab-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nc0ss4key"/><path class="scuo7ib6n"/><path class="njqf7ab-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:person-plus" /></template>
