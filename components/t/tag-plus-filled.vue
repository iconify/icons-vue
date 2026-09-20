<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gsv_mxbid.css';
import '../../css/x/xov4t3bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gsv_mxbid"/><path class="xov4t3bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-plus-filled" /></template>
