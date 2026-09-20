<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwb6_vbxr.css';
import '../../css/z/z5g1e3aps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwb6_vbxr"/><path class="z5g1e3aps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:ruler" /></template>
