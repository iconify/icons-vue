<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbg6tnsmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pbg6tnsmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:tree-unspecified-14" /></template>
