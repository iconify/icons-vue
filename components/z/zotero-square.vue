<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt8bflbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wt8bflbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:zotero-square" /></template>
