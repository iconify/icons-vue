<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3nvxmjsp.css';
import '../../css/g/gsv_mxbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="y3nvxmjsp"/><path class="gsv_mxbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-plus" /></template>
