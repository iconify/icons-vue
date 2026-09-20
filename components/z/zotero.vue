<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1r8mg_ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="k1r8mg_ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:zotero" /></template>
